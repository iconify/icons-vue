<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se5c19beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se5c19beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:phone-arrow-down-left" /></template>
