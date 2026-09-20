<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uob9tnnhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uob9tnnhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-alp" /></template>
