<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcvmepbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcvmepbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:next-filled" /></template>
