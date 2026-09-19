<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efl8wly-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="efl8wly-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:postscript" /></template>
