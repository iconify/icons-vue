<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xummgtbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xummgtbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-down-fill" /></template>
