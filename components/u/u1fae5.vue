<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5xaqcc6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m5xaqcc6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1fae5" /></template>
