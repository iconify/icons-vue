<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmggsfbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmggsfbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-2-fill" /></template>
