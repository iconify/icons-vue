<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3ms7hb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z3ms7hb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-sups" /></template>
