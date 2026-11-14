<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg_48_81b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:usp" /></template>
<style>
.rg_48_81b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.75h10q.169 0 .321.072q.153.072.259.203l4.5 5.499q-.107-.13-.259-.202T21.5 8.25h-19q-.169 0-.321.072t-.259.203l4.5-5.5q.106-.131.259-.203q.152-.072.321-.072m1.417 7H2.5q-.085 0-.168-.019q-.082-.019-.159-.056q-.076-.037-.142-.09t-.119-.119l9.5 12q.054.068.122.122q.117.093.261.133q.143.041.292.024q.148-.017.278-.09t.223-.189l9.5-12q-.053.066-.119.119t-.143.09q-.076.037-.159.056q-.082.019-.167.019h-5.917l-2.856 11.186q-.025.097-.075.185t-.122.159t-.159.122t-.185.075q-.072.018-.146.022t-.147-.007t-.142-.035t-.134-.062q-.063-.038-.118-.087T11.4 21.2t-.077-.126q-.031-.067-.05-.138zm5.617 0L12 17.718L9.966 9.75z");
}

</style>
