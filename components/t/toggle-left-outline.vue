<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nakc4kdbz.css';
import '../../css/w/wglt58box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nakc4kdbz"/><path class="wglt58box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:toggle-left-outline" /></template>
