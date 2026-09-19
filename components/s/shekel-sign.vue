<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iatyzob9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="iatyzob9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shekel-sign" /></template>
