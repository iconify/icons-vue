<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg9366z8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg9366z8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:video-line" /></template>
