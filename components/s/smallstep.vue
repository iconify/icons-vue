<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3267lblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3267lblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smallstep" /></template>
