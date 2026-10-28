<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oovhg-9to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oovhg-9to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splunk-dark" /></template>
