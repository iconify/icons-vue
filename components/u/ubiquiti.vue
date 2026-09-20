<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2s3-4b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2s3-4b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ubiquiti" /></template>
