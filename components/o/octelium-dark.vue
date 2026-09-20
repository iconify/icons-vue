<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0gyg-egc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q0gyg-egc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octelium-dark" /></template>
