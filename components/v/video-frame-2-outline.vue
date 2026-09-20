<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehuuyfbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehuuyfbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-2-outline" /></template>
