<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx0053x8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx0053x8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:uncomfortable-1-filled" /></template>
