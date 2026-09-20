<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gawxdebah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gawxdebah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tab-filled" /></template>
