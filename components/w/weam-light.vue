<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuz27cc_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zuz27cc_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:weam-light" /></template>
