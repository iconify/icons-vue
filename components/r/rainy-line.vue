<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya654m9rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya654m9rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rainy-line" /></template>
