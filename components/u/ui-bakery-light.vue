<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkh80fwxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hkh80fwxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ui-bakery-light" /></template>
