<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3u49vbln.css';
import '../../css/s/sarekibri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3u49vbln"/><path class="sarekibri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:satellite-alt" /></template>
