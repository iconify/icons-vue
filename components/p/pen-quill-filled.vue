<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfpnljh4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfpnljh4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pen-quill-filled" /></template>
