<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2bp_ra0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j2bp_ra0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vala" /></template>
