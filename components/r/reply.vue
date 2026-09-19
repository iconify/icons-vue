<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4lny_b2c.css';
import '../../css/e/ey5fvkbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="p4lny_b2c"/><path class="ey5fvkbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:reply" /></template>
