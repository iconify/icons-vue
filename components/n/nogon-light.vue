<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyim2xbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyim2xbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nogon-light" /></template>
