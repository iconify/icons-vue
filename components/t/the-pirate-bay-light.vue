<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp2kn5b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp2kn5b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-pirate-bay-light" /></template>
