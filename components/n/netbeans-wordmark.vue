<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3gv0lbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x3gv0lbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:netbeans-wordmark" /></template>
