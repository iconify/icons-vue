<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m366bgznx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m366bgznx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paperclip6-filled" /></template>
