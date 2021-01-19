<template lang="html">

  <section class="discord">
    <iframe v-bind:src="'https://discord.com/widget?id=' + this.discordID + '&theme=dark'" width="350" height="500" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
  </section>

</template>

<script lang="js">

  export default  {
    name: 'discord',
    props: {
      discrodid: Object
    },
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="scss">
  .discord {

  }
</style>
