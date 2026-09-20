<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykp0cwbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykp0cwbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sharpness-filled" /></template>
