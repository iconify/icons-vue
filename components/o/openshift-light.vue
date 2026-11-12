<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdt13xckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdt13xckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openshift-light" /></template>
