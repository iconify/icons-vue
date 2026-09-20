<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx4w7qbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx4w7qbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meshping-light" /></template>
