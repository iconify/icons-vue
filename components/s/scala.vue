<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srm-1uqad.css';
import '../../css/s/s6jqjmbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="srm-1uqad"/><path class="s6jqjmbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:scala" /></template>
