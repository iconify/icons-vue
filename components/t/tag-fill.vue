<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3hp3ccry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3hp3ccry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-fill" /></template>
