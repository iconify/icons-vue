<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcfp05mmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":472};
const content = `<path class="lcfp05mmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sound-level-one" /></template>
