<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd040z9hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xd040z9hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnipoly-light" /></template>
