<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho15aj4xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho15aj4xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unregistry-light" /></template>
