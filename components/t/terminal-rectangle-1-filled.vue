<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2u8at1_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2u8at1_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:terminal-rectangle-1-filled" /></template>
