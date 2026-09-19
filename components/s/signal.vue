<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei16dbcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ei16dbcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:signal" /></template>
