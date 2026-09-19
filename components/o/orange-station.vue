<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkop8ti_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gkop8ti_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:orange-station" /></template>
