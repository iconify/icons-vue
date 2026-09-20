<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whqk7pb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whqk7pb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-square-outline" /></template>
