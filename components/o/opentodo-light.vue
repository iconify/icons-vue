<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv8i9sblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dv8i9sblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentodo-light" /></template>
