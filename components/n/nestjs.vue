<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0u_c95tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k0u_c95tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nestjs" /></template>
