<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghip4ybrb.css';
import '../../css/w/wjctu7hsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghip4ybrb"/><path class="wjctu7hsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scroll-20" /></template>
