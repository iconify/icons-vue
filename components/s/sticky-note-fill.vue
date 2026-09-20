<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7lx_xbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7lx_xbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sticky-note-fill" /></template>
