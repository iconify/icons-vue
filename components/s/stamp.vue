<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glyc36bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glyc36bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:stamp" /></template>
