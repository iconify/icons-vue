<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfe1iwbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfe1iwbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wolfram" /></template>
