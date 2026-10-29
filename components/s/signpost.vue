<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynpsrlbdk.css';
import '../../css/u/umcjjfb3i.css';
import '../../css/e/evrpsqb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynpsrlbdk"/><path class="umcjjfb3i"/><path class="evrpsqb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:signpost" /></template>
