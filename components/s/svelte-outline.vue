<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya00f5jao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ya00f5jao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:svelte-outline" /></template>
