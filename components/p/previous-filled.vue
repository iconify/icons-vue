<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ar89bxd.css';
import '../../css/c/c7hrc7bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0ar89bxd"/><path class="c7hrc7bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:previous-filled" /></template>
