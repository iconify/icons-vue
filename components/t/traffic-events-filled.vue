<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sis17fb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sis17fb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:traffic-events-filled" /></template>
