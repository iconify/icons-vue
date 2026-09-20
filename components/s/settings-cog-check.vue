<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b88-1hbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b88-1hbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:settings-cog-check" /></template>
