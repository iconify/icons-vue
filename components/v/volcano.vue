<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puqv6iltn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puqv6iltn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:volcano" /></template>
