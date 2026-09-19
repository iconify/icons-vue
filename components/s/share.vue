<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu9kc8-yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu9kc8-yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:share" /></template>
