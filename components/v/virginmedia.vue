<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfd2wsmwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfd2wsmwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:virginmedia" /></template>
