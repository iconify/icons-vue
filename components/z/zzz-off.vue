<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2csmvb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2csmvb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zzz-off" /></template>
