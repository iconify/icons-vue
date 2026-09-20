<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik95tthsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ik95tthsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retype-light" /></template>
