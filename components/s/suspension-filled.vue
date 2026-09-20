<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4l6txb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4l6txb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suspension-filled" /></template>
