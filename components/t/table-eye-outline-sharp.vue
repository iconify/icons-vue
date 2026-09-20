<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foeranbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-eye-outline-sharp" /></template>
<style>
.foeranbmq {
  fill: currentColor;
  d: path("M4 20V4h16v9.325q-.244-.121-.494-.23t-.506-.19V8.77h-6.5v4.464q-.496.196-.958.49t-.869.68H5V19h2.896q.16.28.329.521l.34.479zm1-6.596h6.5V8.769H5zm0-5.635h14V5H5zm11.135 14q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.383-.94t3.382.94T22 18.309q-.933 1.58-2.483 2.52q-1.55.941-3.382.941m2.62-1.669q1.234-.67 2.072-1.792q-.838-1.123-2.072-1.792q-1.234-.67-2.62-.67t-2.62.67t-2.073 1.792q.839 1.123 2.073 1.792q1.233.67 2.62.67q1.386 0 2.62-.67m-3.327-1.086q-.294-.293-.294-.706t.294-.707t.707-.293t.706.293t.294.707t-.294.707t-.706.293t-.707-.293");
}

</style>
