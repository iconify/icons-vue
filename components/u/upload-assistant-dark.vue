<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn6bxrb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jn6bxrb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:upload-assistant-dark" /></template>
