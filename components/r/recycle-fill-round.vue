<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk8-yaces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8-yaces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-fill-round" /></template>
