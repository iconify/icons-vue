<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfo6yx_nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfo6yx_nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shellhub-light" /></template>
