<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jya9pfbcj.css';
import '../../css/d/d_8ujsb3y.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jya9pfbcj"/><path class="d_8ujsb3y"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:suction-bucket-48" /></template>
