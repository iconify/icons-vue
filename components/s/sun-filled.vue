<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gar44446z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gar44446z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-filled" /></template>
