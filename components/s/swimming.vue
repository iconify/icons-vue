<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6utq58lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6utq58lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:swimming" /></template>
