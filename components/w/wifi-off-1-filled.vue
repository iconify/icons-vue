<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p065d680r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="p065d680r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-off-1-filled" /></template>
