<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0_jmwy_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0_jmwy_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:playlist-fill" /></template>
