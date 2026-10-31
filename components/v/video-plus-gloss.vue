<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsojn1beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsojn1beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:video-plus-gloss" /></template>
