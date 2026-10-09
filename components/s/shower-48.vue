<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch7fqmebm.css';
import '../../css/v/vh9btobqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ch7fqmebm"/><path class="vh9btobqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shower-48" /></template>
