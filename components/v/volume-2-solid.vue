<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czrn7qbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="czrn7qbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:volume-2-solid" /></template>
