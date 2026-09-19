<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh87aubun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh87aubun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:svg-file-filled" /></template>
