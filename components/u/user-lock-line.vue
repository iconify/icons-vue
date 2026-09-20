<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haxv7wbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haxv7wbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-lock-line" /></template>
