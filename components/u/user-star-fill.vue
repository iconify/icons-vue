<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cftcxm0cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cftcxm0cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-star-fill" /></template>
