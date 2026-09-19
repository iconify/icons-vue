<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldt3a1bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ldt3a1bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ship" /></template>
