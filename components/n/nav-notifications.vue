<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6yj_g-sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6yj_g-sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-notifications" /></template>
