<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxzz-cb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxzz-cb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-business" /></template>
