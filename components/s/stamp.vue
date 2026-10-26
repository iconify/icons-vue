<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebcealxyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ebcealxyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:stamp" /></template>
