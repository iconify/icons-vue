<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4kbzy-cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4kbzy-cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:skip-previous-circle" /></template>
