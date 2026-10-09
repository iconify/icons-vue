<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv6l1kbkq.css';
import '../../css/z/znf0au9uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wv6l1kbkq"/><path class="znf0au9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soda-can-20-bold" /></template>
