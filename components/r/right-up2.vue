<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkgktuauf.css';
import '../../css/k/k-vylvb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dkgktuauf"/><path class="k-vylvb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:right-up2" /></template>
