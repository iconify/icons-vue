<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvt5-9uoj.css';
import '../../css/w/w-jbejb_h.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mvt5-9uoj"/><path class="w-jbejb_h"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tunnel-20-bold" /></template>
