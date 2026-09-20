<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zugv0mu1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zugv0mu1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:skip-prev-filled" /></template>
