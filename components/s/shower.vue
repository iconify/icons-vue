<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1ux1bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt1ux1bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shower" /></template>
