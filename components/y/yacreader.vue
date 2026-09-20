<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3a08eaqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3a08eaqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yacreader" /></template>
