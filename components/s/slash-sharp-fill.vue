<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsqfb5o5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqfb5o5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slash-sharp-fill" /></template>
