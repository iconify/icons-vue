<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixrj4gb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixrj4gb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-minimalistic-bold" /></template>
