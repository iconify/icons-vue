<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqfloy9hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqfloy9hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:swear-1-filled" /></template>
