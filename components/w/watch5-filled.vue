<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkwbxybsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkwbxybsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch5-filled" /></template>
