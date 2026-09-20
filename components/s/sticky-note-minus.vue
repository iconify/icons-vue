<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v05r4ubzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v05r4ubzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-minus" /></template>
