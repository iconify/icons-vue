<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq39e_bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iq39e_bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:user" /></template>
