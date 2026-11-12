<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae1idoblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae1idoblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rahoot-light" /></template>
