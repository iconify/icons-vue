<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc9m02b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lc9m02b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:map-marker-solid" /></template>
