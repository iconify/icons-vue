<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3y_m2brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="h3y_m2brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rails" /></template>
