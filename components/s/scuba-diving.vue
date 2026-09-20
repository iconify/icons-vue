<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0n02_zhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scuba-diving" /></template>
<style>
.v0n02_zhm {
  fill: currentColor;
  d: path("m3.904 22.308l-.812-.604l2.62-3.493l.813-4.584q.056-.465.36-.812t.775-.46l9.686-2.932l1.962-4.23l2.596-2.577l.635.596l-2.385 2.573l-1.692 4.407l-4.693 3.347l-6.004 1.907l-1.207 3.304zM3 14.885q-.69 0-1.191-.501t-.501-1.192t.5-1.191T3 11.5t1.191.501t.501 1.191t-.5 1.192q-.502.5-1.192.5m5.823-4.803q-.465.136-.907-.109q-.441-.245-.578-.73q-.136-.465.119-.91t.72-.574l4.262-1.239l.602 2.323z");
}

</style>
