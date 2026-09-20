<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2gxodcss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2gxodcss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scale2-filled" /></template>
