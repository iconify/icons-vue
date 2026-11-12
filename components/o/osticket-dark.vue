<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-j29sr6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-j29sr6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:osticket-dark" /></template>
