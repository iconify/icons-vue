<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-sa-ubgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="m-sa-ubgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plug" /></template>
