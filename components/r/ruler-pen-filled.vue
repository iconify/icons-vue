<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3lxffb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3lxffb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen-filled" /></template>
