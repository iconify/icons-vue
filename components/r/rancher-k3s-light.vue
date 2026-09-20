<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjsav6i6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjsav6i6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-k3s-light" /></template>
