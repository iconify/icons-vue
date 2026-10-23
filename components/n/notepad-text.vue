<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt3dn4bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt3dn4bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:notepad-text" /></template>
