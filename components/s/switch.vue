<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icw9h6w0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="icw9h6w0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:switch" /></template>
