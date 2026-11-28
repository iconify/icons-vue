<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9mk0zbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9mk0zbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-incoming-solid" /></template>
