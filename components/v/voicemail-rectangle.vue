<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lco55sbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lco55sbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:voicemail-rectangle" /></template>
