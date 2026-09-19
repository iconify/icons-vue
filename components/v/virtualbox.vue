<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg4w-xbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":512};
const content = `<path class="wg4w-xbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:virtualbox" /></template>
