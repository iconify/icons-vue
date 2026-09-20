<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7gb8od4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7gb8od4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:manjaro-logo-block" /></template>
