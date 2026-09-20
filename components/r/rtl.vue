<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6hkx8byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":12};
const content = `<path class="b6hkx8byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:rtl" /></template>
