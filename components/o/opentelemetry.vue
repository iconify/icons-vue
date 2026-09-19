<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ulv6bdt.css';
import '../../css/k/ku4u7fl3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z6ulv6bdt"/><path class="ku4u7fl3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opentelemetry" /></template>
