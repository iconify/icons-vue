<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv6kxplzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv6kxplzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swizzin-light" /></template>
