<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbzwxtyqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbzwxtyqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-landing-48-bold" /></template>
