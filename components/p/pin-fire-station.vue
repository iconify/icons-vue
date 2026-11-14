<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a806ybfyn"/><path class="c_t4ynt_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-fire-station" /></template>
<style>
.a806ybfyn {
  d: path("M12.401 21H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-8.785q0-.222.055-.436q.055-.215.162-.409t.26-.355q.152-.162.339-.28l7.75-4.895q.104-.066.217-.116q.112-.051.231-.085q.118-.034.241-.052q.122-.017.245-.017t.245.017t.241.052t.231.085t.217.116l7.75 4.895q.187.118.339.28q.152.161.26.355q.107.194.162.409t.055.436v.609");
}

.c_t4ynt_a {
  d: path("M6.5 13h3a1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 9.5 21h-3A1.5 1.5 0 0 1 5 19.5v-5A1.5 1.5 0 0 1 6.5 13M18 21.5c-2.25 0-3.5-1.75-3.5-3.5s1.25-2.5 2-3.5c.25 1.25 1 1.75 1.5 1.75c0-1.5.75-2.5 1.5-3.25c1 2 2 3.25 2 5s-1.25 3.5-3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
