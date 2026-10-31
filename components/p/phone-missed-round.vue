<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ksbvb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ksbvb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-missed-round" /></template>
