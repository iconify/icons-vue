<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygvme9b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygvme9b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-2" /></template>
