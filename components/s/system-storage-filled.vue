<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sul7jy1tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sul7jy1tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-storage-filled" /></template>
