<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od3nh1bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od3nh1bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:operational-dark" /></template>
