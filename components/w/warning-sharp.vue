<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wszqcccvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wszqcccvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:warning-sharp" /></template>
