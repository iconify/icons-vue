<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njc7jtbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njc7jtbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-leap" /></template>
