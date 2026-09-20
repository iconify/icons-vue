<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svg5nkb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svg5nkb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ruler-filled" /></template>
