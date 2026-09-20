<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ljl_mpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ljl_mpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-down-alt-1-line" /></template>
