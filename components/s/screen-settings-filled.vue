<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjjp3cbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjjp3cbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-settings-filled" /></template>
