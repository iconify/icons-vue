<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6yvi_chi.css';
import '../../css/t/t8i6bfbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6yvi_chi secondary"/><path class="primary t8i6bfbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stop-duo" /></template>
