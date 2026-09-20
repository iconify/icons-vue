<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urz7vu6vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urz7vu6vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remoteterm-light" /></template>
