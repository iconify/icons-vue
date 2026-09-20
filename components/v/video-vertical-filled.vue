<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp0xnpbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp0xnpbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-vertical-filled" /></template>
