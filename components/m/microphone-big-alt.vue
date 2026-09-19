<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvrzt5bkz.css';
import '../../css/f/fhwkkcqly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvrzt5bkz"/><path class="fhwkkcqly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-big-alt" /></template>
