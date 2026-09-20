<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u643a_fwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u643a_fwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plc-tag" /></template>
