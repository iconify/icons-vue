<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3k6s3b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3k6s3b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pdf-01" /></template>
