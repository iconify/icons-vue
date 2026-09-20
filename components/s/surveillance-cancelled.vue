<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a84atto0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a84atto0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:surveillance-cancelled" /></template>
