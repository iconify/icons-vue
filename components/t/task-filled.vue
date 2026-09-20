<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_hxwwbci.css';
import '../../css/t/tf_hn4bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_hxwwbci"/><path class="tf_hn4bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-filled" /></template>
