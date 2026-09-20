<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgy_7bltc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgy_7bltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:organization-16" /></template>
