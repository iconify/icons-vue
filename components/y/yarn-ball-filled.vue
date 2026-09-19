<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8-h7-bhg.css';
import '../../css/h/h-_epdppu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8-h7-bhg"/><path class="h-_epdppu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:yarn-ball-filled" /></template>
