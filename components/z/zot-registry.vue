<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phrl5wbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phrl5wbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zot-registry" /></template>
