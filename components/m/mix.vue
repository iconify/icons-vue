<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8n35mg7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8n35mg7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mix" /></template>
