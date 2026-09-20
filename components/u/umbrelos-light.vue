<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oue_9j4jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oue_9j4jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:umbrelos-light" /></template>
