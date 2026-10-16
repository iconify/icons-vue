<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6ncrt0qq.css';
import '../../css/j/j6-8hdc3j.css';
import '../../css/q/q24aqk9up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k6ncrt0qq"/><path class="j6-8hdc3j"/><path class="q24aqk9up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-source-20" /></template>
