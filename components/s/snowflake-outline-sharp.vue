<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7-wz07cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:snowflake-outline-sharp" /></template>
<style>
.b7-wz07cy {
  fill: currentColor;
  d: path("M11.5 21.5v-2.402l-2.061 1.716l-.647-.756L11.5 17.78v-4.896l-4.262 2.438l-.617 3.475l-.994-.177l.49-2.652l-2.1 1.233l-.5-.879l2.1-1.213l-2.533-.898l.349-.933l3.305 1.179L10.981 12L6.739 9.561l-3.306 1.185l-.348-.938l2.532-.893l-2.1-1.213l.5-.879l2.1 1.233l-.49-2.652l.994-.177l.618 3.475l4.261 2.439V6.244L8.792 3.967l.646-.755L11.5 4.927V2.5h1v2.427l2.042-1.716l.646.756L12.5 6.244v4.897l4.237-2.439l.617-3.475l.994.177l-.49 2.652l2.1-1.233l.5.879l-2.1 1.214l2.532.892l-.348.938l-3.306-1.184L13 12l4.237 2.458l3.305-1.18l.348.934l-2.532.898l2.1 1.213l-.5.879l-2.1-1.233l.49 2.652l-.994.177l-.618-3.475l-4.236-2.438v4.896l2.689 2.277l-.647.756l-2.042-1.716V21.5z");
}

</style>
