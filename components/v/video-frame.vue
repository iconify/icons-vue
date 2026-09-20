<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aujvfs0gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aujvfs0gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-frame" /></template>
