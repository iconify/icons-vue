<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx9-6wbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx9-6wbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-k3os-dark" /></template>
