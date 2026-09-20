<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptc16vbmh.css';
import '../../css/p/pvum3qbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptc16vbmh"/><path class="pvum3qbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:surprised-filled" /></template>
