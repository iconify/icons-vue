<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eporl6ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eporl6ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:prisma" /></template>
