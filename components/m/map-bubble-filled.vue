<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq7wclblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq7wclblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-bubble-filled" /></template>
