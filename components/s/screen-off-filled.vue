<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbf6qccau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nbf6qccau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:screen-off-filled" /></template>
