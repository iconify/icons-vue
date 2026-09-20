<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t09xm3etv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t09xm3etv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-filled" /></template>
