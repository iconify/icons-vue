<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js4054bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="js4054bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubesync" /></template>
