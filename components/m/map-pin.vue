<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnxg3b-j.css';
import '../../css/s/sxj-2bc0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbnxg3b-j wm-k"/><path class="sxj-2bc0x wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:map-pin" /></template>
