<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhj-4g1kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhj-4g1kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-cut2-filled" /></template>
