<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc_2esbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_2esbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:t-shirt-outline" /></template>
