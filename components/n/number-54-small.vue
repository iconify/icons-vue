<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gird6ac5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gird6ac5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-54-small" /></template>
