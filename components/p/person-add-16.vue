<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_u0zbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ib_u0zbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-add-16" /></template>
