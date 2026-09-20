<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dirlafbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dirlafbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upload-cloud-2-fill" /></template>
