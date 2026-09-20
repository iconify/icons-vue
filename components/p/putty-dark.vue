<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8k7r890n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k8k7r890n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:putty-dark" /></template>
