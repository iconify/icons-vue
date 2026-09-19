<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3p49obkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3p49obkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:whiteboard-filled" /></template>
