<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0f9s_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k0f9s_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:quote-solid" /></template>
