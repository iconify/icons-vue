<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kht4czj5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="kht4czj5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:propeller-1" /></template>
