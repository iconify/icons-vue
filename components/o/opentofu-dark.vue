<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y540id84w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y540id84w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentofu-dark" /></template>
