<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oab43-7av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oab43-7av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vespa" /></template>
