<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyx_jbcae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyx_jbcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:street-view" /></template>
