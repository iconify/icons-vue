<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohi4kqh9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ohi4kqh9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minimise-outline" /></template>
