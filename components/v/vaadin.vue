<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpzcf90uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kpzcf90uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vaadin" /></template>
