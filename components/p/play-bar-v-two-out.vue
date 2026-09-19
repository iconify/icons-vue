<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcr7icbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcr7icbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-v-two-out" /></template>
