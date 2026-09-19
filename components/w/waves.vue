<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdv-he75m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xdv-he75m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:waves" /></template>
