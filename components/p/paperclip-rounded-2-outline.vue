<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3r6oyb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3r6oyb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-rounded-2-outline" /></template>
