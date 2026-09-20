<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix9-8kbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ix9-8kbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-row-above" /></template>
