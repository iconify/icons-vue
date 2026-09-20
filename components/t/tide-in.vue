<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyxfpkv0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyxfpkv0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tide-in" /></template>
