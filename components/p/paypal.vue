<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fezhcwz_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":488};
const content = `<path class="fezhcwz_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:paypal" /></template>
