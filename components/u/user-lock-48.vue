<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmbcisb5f.css';
import '../../css/k/ktb8eibqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmbcisb5f"/><path class="ktb8eibqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-lock-48" /></template>
