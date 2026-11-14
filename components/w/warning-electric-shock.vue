<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1filsbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:warning-electric-shock" /></template>
<style>
.f1filsbtg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.014 15.997l-5.058-9.184Q13.994 5.067 12 5.067T9.044 6.813l-5.058 9.184q-.929 1.687.051 3.345Q5.016 21 6.942 21h10.116q1.926 0 2.905-1.658q.98-1.658.051-3.345M11.426 13H14q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .246-.145.444l-2.75 3.75q-.088.12-.216.197t-.275.1t-.292-.013q-.145-.035-.266-.123q-.059-.044-.109-.098t-.088-.118q-.039-.063-.064-.133q-.025-.069-.036-.142q-.012-.073-.008-.147q.003-.074.021-.145q.017-.072.048-.139q.032-.067.075-.127L12.52 14.5H10q-.233 0-.425-.132q-.061-.042-.112-.095t-.092-.115t-.068-.13t-.04-.141t-.013-.147t.016-.146t.045-.14t.071-.129l2.75-4q.042-.061.095-.112t.115-.092t.13-.068t.141-.04T12.76 9t.146.016t.14.045t.129.071t.112.095t.092.115t.068.13t.04.141t.013.147t-.016.146t-.045.14t-.071.129z");
}

</style>
