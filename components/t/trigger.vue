<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh4pik2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nh4pik2np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:trigger" /></template>
