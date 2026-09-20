<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhge7bbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhge7bbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-line" /></template>
