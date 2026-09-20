<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsrjnu5_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zsrjnu5_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:seedling" /></template>
