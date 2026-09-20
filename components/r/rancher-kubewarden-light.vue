<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri65of2nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ri65of2nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-kubewarden-light" /></template>
