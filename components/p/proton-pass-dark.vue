<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axa1u9_az.css';
import '../../css/o/o8wjvtbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axa1u9_az"/><path class="o8wjvtbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-pass-dark" /></template>
