<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tboc6jd8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tboc6jd8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:minimize" /></template>
