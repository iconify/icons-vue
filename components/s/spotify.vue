<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a26dkh2yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a26dkh2yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:spotify" /></template>
