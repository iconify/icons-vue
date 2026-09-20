<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5277z8hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5277z8hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rundeck-light" /></template>
