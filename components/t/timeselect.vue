<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjaiwl-7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mjaiwl-7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:timeselect" /></template>
