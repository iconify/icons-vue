<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rht3leb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":281.25,"height":281.25};
const content = `<path class="rht3leb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:merlin" /></template>
