<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gybwtkv2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gybwtkv2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-1" /></template>
