<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm82tsche.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm82tsche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sticky-note-filled" /></template>
