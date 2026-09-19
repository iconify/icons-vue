<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ror7eiqam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ror7eiqam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:troubleshooting" /></template>
