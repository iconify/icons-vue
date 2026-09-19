<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqltz0bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bqltz0bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:photonengine" /></template>
