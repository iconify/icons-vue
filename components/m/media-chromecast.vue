<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmuo2gb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmuo2gb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-chromecast" /></template>
