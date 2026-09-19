<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckad6q9jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ckad6q9jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:test-tube-filled" /></template>
