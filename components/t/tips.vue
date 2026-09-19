<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="u_y20sbas"/><path class="uhoe_jbca"/><path class="jcbrt7ntz"/></g><path class="gv6c9-bcv"/><path class="n1icjebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tips" /></template>
<style>
.gv6c9-bcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.702 17.014c1.108-.159 2.188-.139 3.418-.067c-.112 2.417-.326 4.527-.332 7.102c-.008 3.267.833 4.86 3.51 2.513");
}

.jcbrt7ntz {
  d: path("m36.166 39.67l.015.27c.076 1.416-1.145 2.56-2.567 2.56H14.386c-1.422 0-2.643-1.144-2.567-2.56l.015-.27");
}

.n1icjebag {
  fill: currentColor;
  d: path("M25.25 13.404a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.u_y20sbas {
  d: path("M11.732 5.5h24.536c1.994 0 3.492 1.608 3.6 3.598l1.212 22.579c.107 1.99-1.606 3.598-3.6 3.598H10.52c-1.994 0-3.706-1.608-3.6-3.598l1.213-22.58c.107-1.99 1.605-3.597 3.6-3.597");
}

.uhoe_jbca {
  d: path("m38.812 35.022l.082 1.542c.094 1.734-1.4 3.135-3.139 3.135h-23.51c-1.74 0-3.233-1.4-3.14-3.135l.083-1.542");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
