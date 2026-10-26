<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6f6kcstl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6f6kcstl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:minus" /></template>
