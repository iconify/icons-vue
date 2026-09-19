<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="f00uefbuw"/><g class="y9tr6bcfx"><circle class="ksyzkhkyr"/><path class="qv9hypbpo"/><path class="s2v_4fbbn"/><circle class="pxxhcdsto"/></g><path class="rkkxc2bqt"/><path class="np8alf41n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sky" /></template>
<style>
.f00uefbuw {
  cx: 33.542px;
  cy: 21.309px;
  r: 2.809px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ksyzkhkyr {
  cx: 19.427px;
  cy: 22.422px;
  r: 2.809px;
}

.np8alf41n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 23.918c-.066 4.048 1.354 8.422.517 12.221l.88 2.474l2.072-2.081c.164-4.808-1.677-8.558-1.294-12.653m-13.615.829c.358.88.529 3.84.5 4.694m-3.427-4.486c-.584.75-3.06 2.377-3.815 2.78");
}

.pxxhcdsto {
  cx: 24.712px;
  cy: 10.898px;
  r: 1.431px;
}

.qv9hypbpo {
  d: path("M21.06 24.708c3.578 2.87 5.989 5.985 8.751 9.978c0 0-7.815 1.077-12.345.78c-3.048-.201-8.897-3.089-8.897-3.089c5.663-2.777 7.843-5.146 9.564-7.461");
}

.rkkxc2bqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.675 23.88v1.389s2.178 1.286 2.394 2.393c.448 2.299.272 7.07.122 9.484c-.05.811-.782 1.467-1.595 1.467h-4.109c-.813 0-1.533-.657-1.576-1.469c-.126-2.37-.273-7.003.103-9.323c.188-1.157 2.487-2.486 2.487-2.486v-1.417M42.5 35.505l-5.223-.005m-20.1.005L5.5 35.5");
}

.s2v_4fbbn {
  d: path("m23.333 35.352l.563 2.199a.64.64 0 0 1-.609.799l-6.398.118a.618.618 0 0 1-.61-.77l.586-2.3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
