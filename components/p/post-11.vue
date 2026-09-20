<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejeoy_boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ejeoy_boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:post-11" /></template>
