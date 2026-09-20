<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_63-l9bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_63-l9bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vana" /></template>
