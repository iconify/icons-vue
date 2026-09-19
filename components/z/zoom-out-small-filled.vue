<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd446ibrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kd446ibrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zoom-out-small-filled" /></template>
