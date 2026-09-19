<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt18aubkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="mt18aubkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:quora" /></template>
