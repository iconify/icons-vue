<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qru5rt3-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qru5rt3-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:x-circle-solid" /></template>
