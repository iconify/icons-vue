<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls9fy_b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ls9fy_b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:swerve-filled" /></template>
