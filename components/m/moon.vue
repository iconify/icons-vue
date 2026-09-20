<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbzwcrb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbzwcrb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:moon" /></template>
