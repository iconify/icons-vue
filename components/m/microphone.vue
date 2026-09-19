<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkb_xbcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkb_xbcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:microphone" /></template>
