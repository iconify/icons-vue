<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2apqubdg.css';
import '../../css/o/oj1zdwuco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d2apqubdg"/><path class="oj1zdwuco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mouse-right-button-16" /></template>
