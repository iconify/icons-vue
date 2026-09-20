<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyfrh3d4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyfrh3d4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-linear" /></template>
