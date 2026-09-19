<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck1713rkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck1713rkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:underline" /></template>
