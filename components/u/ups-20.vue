<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzgrz9d2f.css';
import '../../css/j/jmwc4n-6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hzgrz9d2f"/><path class="jmwc4n-6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ups-20" /></template>
