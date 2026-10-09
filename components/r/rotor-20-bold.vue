<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewqmb9jcq.css';
import '../../css/g/gykt9mb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewqmb9jcq"/><path class="gykt9mb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotor-20-bold" /></template>
