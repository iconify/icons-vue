<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieuo3rbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieuo3rbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:snapchat-alt" /></template>
