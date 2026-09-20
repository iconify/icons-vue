<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw9twle1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw9twle1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-square-outline" /></template>
