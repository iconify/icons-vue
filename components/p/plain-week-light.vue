<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2i8szb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2i8szb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plain-week-light" /></template>
