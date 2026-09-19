<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4t2u9hnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="m4t2u9hnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:solar-panel" /></template>
