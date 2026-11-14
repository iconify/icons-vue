<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_oj3k51e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-star" /></template>
<style>
.a_oj3k51e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.796l-7.5-2.75Q12.133 2 12 2t-.258.046l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225v6q0 7.276 7.973 10.447q.133.053.277.053t.277-.053Q20.25 18.776 20.25 11.5v-6q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11M13.2 8.615l.162.368q.177.399.611.443l.401.041q.851.088 1.114.9t-.373 1.383l-.298.267q-.327.292-.235.719l.085.392q.182.836-.511 1.339q-.692.504-1.431.073l-.347-.202q-.378-.22-.756 0l-.347.202q-.739.431-1.431-.073q-.693-.503-.511-1.339l.085-.392q.092-.427-.234-.718l-.3-.269q-.636-.569-.372-1.381q.263-.813 1.113-.901l.401-.041q.435-.044.612-.444l.162-.367q.346-.783 1.2-.783t1.2.782z");
}

</style>
