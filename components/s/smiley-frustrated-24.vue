<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbrkzh8sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbrkzh8sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:smiley-frustrated-24" /></template>
