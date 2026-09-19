<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_7q0zb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_7q0zb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:target" /></template>
