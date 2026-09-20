<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce4r_lgpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce4r_lgpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:receipt-solid" /></template>
