<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev7a6mbod.css';
import '../../css/h/hvelf-bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev7a6mbod"/><path class="hvelf-bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shopping-bag-alt" /></template>
