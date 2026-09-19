<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfaa8oorn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="kfaa8oorn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-field" /></template>
