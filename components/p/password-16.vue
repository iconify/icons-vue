<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtr2w7blj.css';
import '../../css/q/qvhmvvbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mtr2w7blj"/><path clip-rule="evenodd" class="qvhmvvbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:password-16" /></template>
