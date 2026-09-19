<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egpruf3ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="egpruf3ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sketch" /></template>
