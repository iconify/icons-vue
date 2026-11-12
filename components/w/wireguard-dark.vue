<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk0h4l9rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk0h4l9rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wireguard-dark" /></template>
