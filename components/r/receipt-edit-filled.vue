<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0-laacgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0-laacgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-edit-filled" /></template>
