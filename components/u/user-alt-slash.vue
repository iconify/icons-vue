<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyt06xb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vyt06xb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:user-alt-slash" /></template>
