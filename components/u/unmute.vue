<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el2e-84ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="el2e-84ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:unmute" /></template>
