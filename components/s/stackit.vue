<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju3_qt3um.css';
import '../../css/j/jlb1dbrgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ju3_qt3um"/><path class="jlb1dbrgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stackit" /></template>
