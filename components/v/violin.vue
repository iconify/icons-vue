<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp7bhvbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kp7bhvbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:violin" /></template>
