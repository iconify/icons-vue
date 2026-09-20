<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woc9o0epe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woc9o0epe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-15-small" /></template>
