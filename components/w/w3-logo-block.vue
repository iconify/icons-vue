<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hho5p9bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hho5p9bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:w3-logo-block" /></template>
