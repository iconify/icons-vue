<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csmpox66s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csmpox66s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pin-filled" /></template>
