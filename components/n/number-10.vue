<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc1jkgb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc1jkgb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-10" /></template>
