<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu6zwruqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu6zwruqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-carport" /></template>
