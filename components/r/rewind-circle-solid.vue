<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhd-5gbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nhd-5gbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-circle-solid" /></template>
