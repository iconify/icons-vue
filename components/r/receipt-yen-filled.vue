<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiho0ob9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiho0ob9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-yen-filled" /></template>
