<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no7_26bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no7_26bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:teacup-fill" /></template>
