<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tspdbnbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tspdbnbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nitter-dark" /></template>
