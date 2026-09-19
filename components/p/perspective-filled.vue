<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgzhcnzbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgzhcnzbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:perspective-filled" /></template>
