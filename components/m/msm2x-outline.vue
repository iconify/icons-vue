<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pix9i5bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pix9i5bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:msm2x-outline" /></template>
