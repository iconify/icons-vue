<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3pcv7b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3pcv7b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:smartos" /></template>
