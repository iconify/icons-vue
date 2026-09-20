<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3k7eu14g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x3k7eu14g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tenge-solid" /></template>
