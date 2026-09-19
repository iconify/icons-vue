<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk--8mbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tk--8mbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:radio-20-solid" /></template>
