<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jztwacb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jztwacb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-slash" /></template>
