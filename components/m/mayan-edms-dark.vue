<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo14xkb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qo14xkb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mayan-edms-dark" /></template>
