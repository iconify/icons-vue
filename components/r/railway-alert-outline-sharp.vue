<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vphmaac-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:railway-alert-outline-sharp" /></template>
<style>
.vphmaac-e {
  fill: currentColor;
  d: path("M4.104 6.539h6.446zM16 13H4zM4.385 20.462V20l1.5-1q-1.2 0-2.043-.842T3 16.115V7q0-1.61 1.851-2.305T10.986 4q-.132.239-.245.479t-.191.515q-3.185.05-4.678.416q-1.493.365-1.768 1.129h6.144q-.017.25-.017.5t.036.5H4V12h8.814q.386.312.825.565t.934.435H4v3.116q0 .778.553 1.331T5.885 18h8.23q.78 0 1.332-.553q.553-.553.553-1.331v-2.768q.25.037.5.037t.5-.018v2.787q0 1.2-.842 2.023q-.843.823-2.043.823l1.5 1v.462zM16.615 11q-1.67 0-2.835-1.164Q12.616 8.67 12.616 7q0-1.666 1.161-2.833T16.616 3q1.67 0 2.835 1.165Q20.616 5.329 20.616 7T19.44 9.836T16.616 11m-.385-3.384H17v-3h-.77zm.384 1.846q.2 0 .322-.131q.12-.131.14-.312q0-.2-.13-.34q-.131-.14-.331-.14t-.331.13t-.131.331t.13.33q.132.132.332.132m-5.823 6.831q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323");
}

</style>
