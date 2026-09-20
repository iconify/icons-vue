<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-jpfh4yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-eye-outline" /></template>
<style>
.p-jpfh4yd {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v7.709q-.244-.121-.494-.23t-.506-.19V8.77h-6.5v4.464q-.496.196-.958.49t-.869.68H5v3.982q0 .269.173.442t.443.173h2.28q.16.28.329.521l.34.479zM5 13.404h6.5V8.769H5zm0-5.635h14V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616zm11.135 14q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.383-.94t3.382.94T22 18.309q-.933 1.58-2.483 2.52q-1.55.941-3.382.941m2.62-1.669q1.234-.67 2.072-1.792q-.838-1.123-2.072-1.792q-1.234-.67-2.62-.67t-2.62.67t-2.073 1.792q.839 1.123 2.073 1.792q1.233.67 2.62.67q1.386 0 2.62-.67m-3.327-1.086q-.294-.293-.294-.706t.294-.707t.707-.293t.706.293t.294.707t-.294.707t-.706.293t-.707-.293");
}

</style>
