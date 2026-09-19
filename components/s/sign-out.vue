<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2_mexoqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2_mexoqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sign-out" /></template>
