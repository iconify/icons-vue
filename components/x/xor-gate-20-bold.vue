<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzflhmqcl.css';
import '../../css/h/hvkkpmbju.css';
import '../../css/h/h8goprb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzflhmqcl"/><path class="hvkkpmbju"/><path class="h8goprb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:xor-gate-20-bold" /></template>
