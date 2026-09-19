<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxibtf8_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxibtf8_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:save-outline" /></template>
