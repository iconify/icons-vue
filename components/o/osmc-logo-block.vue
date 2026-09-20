<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lawae4buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lawae4buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:osmc-logo-block" /></template>
