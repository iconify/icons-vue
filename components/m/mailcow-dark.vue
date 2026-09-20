<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uotgo6lhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uotgo6lhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailcow-dark" /></template>
