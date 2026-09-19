<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp5c0ubxx.css';
import '../../css/h/h5e9s-b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp5c0ubxx"/><path clip-rule="evenodd" class="h5e9s-b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:tube-outline" /></template>
