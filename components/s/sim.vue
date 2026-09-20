<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5v32bcqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r5v32bcqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sim" /></template>
