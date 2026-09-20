<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5t37qwas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5t37qwas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teamviewer" /></template>
