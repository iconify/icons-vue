<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h94eycfhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h94eycfhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:warracker-light" /></template>
