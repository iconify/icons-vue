<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgk4045dp.css';
import '../../css/e/e26d43smq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mgk4045dp"/><path class="e26d43smq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shop-solid" /></template>
