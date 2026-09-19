<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzzrnmb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xzzrnmb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pager" /></template>
