<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqt-fc2_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqt-fc2_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane" /></template>
