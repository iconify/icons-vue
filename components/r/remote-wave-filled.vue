<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9dg3bzxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9dg3bzxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:remote-wave-filled" /></template>
