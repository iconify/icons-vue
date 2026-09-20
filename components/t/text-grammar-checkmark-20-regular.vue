<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bq08vbb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-grammar-checkmark-20-regular" /></template>
<style>
.bq08vbb9t {
  fill: currentColor;
  d: path("M17.5 5a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm0 3a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zM9 14.5q0-.252.022-.5H2.5a.5.5 0 0 0 0 1h6.522A6 6 0 0 1 9 14.5m.6-2.5q.276-.538.657-1H2.5a.5.5 0 0 0 0 1zm4.9-2a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-1.121 5.769l-.999-1.227l-.063-.064a.5.5 0 0 0-.712.696l1.34 1.645l.066.067a.5.5 0 0 0 .666-.02l3.512-3.641l.06-.068a.5.5 0 0 0-.749-.657z");
}

</style>
