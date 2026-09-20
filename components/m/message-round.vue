<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuf2acihv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuf2acihv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-round" /></template>
