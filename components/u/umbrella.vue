<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ovouiea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_ovouiea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:umbrella" /></template>
