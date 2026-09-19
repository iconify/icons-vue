<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v763qvp_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="v763qvp_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sketch" /></template>
