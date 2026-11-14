<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq3vz4buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-badge" /></template>
<style>
.nq3vz4buh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.796l-7.5-2.75Q12.133 2 12 2t-.258.046l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225v6q0 7.276 7.973 10.447q.133.053.277.053t.277-.053Q20.25 18.776 20.25 11.5v-6q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11m-6.327 2.515l.379.821q.186.401.627.433l.867.062q.994.071 1.343 1.005q.348.935-.358 1.64l-.682.681q-.288.289-.203.688l.204.952q.211.986-.595 1.591q-.807.606-1.695.127l-.962-.517q-.356-.192-.712-.001l-.963.519q-.887.478-1.694-.128q-.806-.605-.595-1.591l.204-.952q.085-.399-.203-.688l-.682-.682q-.706-.704-.358-1.639q.349-.934 1.344-1.005l.865-.062q.442-.032.628-.434l.379-.82q.423-.916 1.431-.916t1.431.916");
}

</style>
