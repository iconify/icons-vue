<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj1ucbbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj1ucbbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:window-filled" /></template>
