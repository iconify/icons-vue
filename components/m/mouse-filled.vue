<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-y12rbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-y12rbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mouse-filled" /></template>
