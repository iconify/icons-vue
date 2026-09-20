<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpg_34pwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpg_34pwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:myip-light" /></template>
