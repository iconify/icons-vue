<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ro5bbhu.css';
import '../../css/c/ck3x9ggdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ro5bbhu"/><path clip-rule="evenodd" class="ck3x9ggdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tickets-3" /></template>
