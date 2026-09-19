<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvrzt5bkz.css';
import '../../css/f/fdvvb9b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvrzt5bkz"/><path class="fdvvb9b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-big-filled" /></template>
