<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba4911_sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba4911_sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vowpal-wabbit" /></template>
