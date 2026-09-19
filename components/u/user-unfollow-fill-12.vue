<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m23wrpw-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m23wrpw-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-unfollow-fill-12" /></template>
