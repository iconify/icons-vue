<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h02w-12-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h02w-12-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sun2-filled" /></template>
