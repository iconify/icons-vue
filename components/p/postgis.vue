<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_c_3dfgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c_c_3dfgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:postgis" /></template>
