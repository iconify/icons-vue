<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjdb9lb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-transfer-outline-sharp" /></template>
<style>
.cjdb9lb8o {
  fill: currentColor;
  d: path("M7.77 18v2H6.538v-2.396q-.489-.212-1.014-.901T5 15.115V6.421L1.887 3.308l.713-.714l19.223 19.223l-.713.714l-5.04-5.04h1.426V20h-1.265v-2zM8 17h7.579l-5-5H6v3q0 .825.588 1.413T8 17m10.84-.977l-.84-.84V12h-3.183l-1-1H18V6.539H9.356l-1-1h9.563q-.26-.772-1.603-1.155Q14.973 4 12.012 4q-1.699 0-2.83.13t-1.84.395l-.755-.756q.86-.384 2.199-.577T12 3q3.762 0 5.38.694T19 6v9.116q0 .234-.046.456t-.114.451m-9.547-.73q.322-.322.322-.793t-.322-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M6 11h3.579L6 7.421zm2.356-5.462h9.563zM14.817 12");
}

</style>
