<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shxpmvb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shxpmvb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zzz" /></template>
