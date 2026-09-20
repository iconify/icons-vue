<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0r5uinwc.css';
import '../../css/u/u1-hezbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0r5uinwc"/><path class="u1-hezbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:print" /></template>
