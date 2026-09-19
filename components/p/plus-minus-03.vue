<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opogr211w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opogr211w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus-minus-03" /></template>
