<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrl9yvbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rrl9yvbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sqlalchemy-wordmark" /></template>
