<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc-mqm-1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nc-mqm-1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wallaby" /></template>
