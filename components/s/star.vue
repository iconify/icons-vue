<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne3uqob6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ne3uqob6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:star" /></template>
