<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1-7subbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k1-7subbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sun-solid" /></template>
