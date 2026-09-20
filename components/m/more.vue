<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka3xe-i4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka3xe-i4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:more" /></template>
