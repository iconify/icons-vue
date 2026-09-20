<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6fvybcit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j6fvybcit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-12" /></template>
