<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-osi3jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wg-osi3jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-happy-solid" /></template>
