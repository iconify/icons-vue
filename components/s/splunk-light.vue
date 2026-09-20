<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqns204fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eqns204fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:splunk-light" /></template>
