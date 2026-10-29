<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heb0llboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heb0llboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vr-headset-solid" /></template>
