<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwe9ecw5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uwe9ecw5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-out-16" /></template>
