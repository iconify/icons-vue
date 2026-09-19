<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6v6ah50v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="r6v6ah50v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:sd-card" /></template>
