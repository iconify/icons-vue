<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2vjnjw9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q2vjnjw9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-snowboarding-downhill" /></template>
