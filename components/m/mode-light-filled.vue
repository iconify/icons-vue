<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s57kuzu5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="s57kuzu5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mode-light-filled" /></template>
