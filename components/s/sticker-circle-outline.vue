<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-iwqxvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo-iwqxvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-circle-outline" /></template>
