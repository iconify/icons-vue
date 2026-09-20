<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iek8-0b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iek8-0b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh2-filled" /></template>
