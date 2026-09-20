<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7w7ozbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7w7ozbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metadata-remote-light" /></template>
