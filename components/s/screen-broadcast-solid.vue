<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dra7irbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dra7irbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-broadcast-solid" /></template>
