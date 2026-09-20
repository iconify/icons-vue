<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjo5syb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjo5syb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signal" /></template>
