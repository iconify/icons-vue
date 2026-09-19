<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clpvn6bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":472};
const content = `<path class="clpvn6bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sound-level-two" /></template>
