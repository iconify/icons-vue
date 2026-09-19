<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtdb2rb_j.css';
import '../../css/d/dmcux5bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="dtdb2rb_j"/><path class="dmcux5bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:mobile-phone-fill-16" /></template>
