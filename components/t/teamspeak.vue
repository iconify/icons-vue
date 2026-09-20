<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x70cer9yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x70cer9yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:teamspeak" /></template>
