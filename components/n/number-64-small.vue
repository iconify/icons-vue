<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2y77wbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2y77wbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-64-small" /></template>
