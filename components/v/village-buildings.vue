<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esz_ho-hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="esz_ho-hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:village-buildings" /></template>
