<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd1tw0gyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd1tw0gyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-blocked-filled" /></template>
