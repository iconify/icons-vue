<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5y6i5byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5y6i5byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:video-outline" /></template>
