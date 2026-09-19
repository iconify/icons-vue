<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djj-u_w3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="djj-u_w3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:right-angle" /></template>
