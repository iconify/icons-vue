<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx9z7-b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tx9z7-b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pen-alt" /></template>
