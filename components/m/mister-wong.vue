<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k05qhhbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":488};
const content = `<path class="k05qhhbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mister-wong" /></template>
