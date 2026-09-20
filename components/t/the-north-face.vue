<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uft4gr4ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uft4gr4ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-north-face" /></template>
