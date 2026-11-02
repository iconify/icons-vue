<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji4o9ze8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji4o9ze8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-3-line" /></template>
