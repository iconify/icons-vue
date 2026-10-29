<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiy69acjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy69acjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:play-solid" /></template>
