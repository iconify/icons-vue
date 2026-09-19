<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgh63ebfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgh63ebfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:x-square-filled" /></template>
