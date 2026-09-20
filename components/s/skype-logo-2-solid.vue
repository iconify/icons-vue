<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdtyjbcdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdtyjbcdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:skype-logo-2-solid" /></template>
