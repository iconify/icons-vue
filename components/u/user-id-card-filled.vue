<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6r5qbbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6r5qbbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-id-card-filled" /></template>
