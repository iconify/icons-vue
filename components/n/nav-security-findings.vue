<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc0h2eget.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oc0h2eget"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-security-findings" /></template>
