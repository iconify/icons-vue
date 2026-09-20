<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tja7qfb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tja7qfb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:number-filled" /></template>
