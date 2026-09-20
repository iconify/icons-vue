<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3z0rjreb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c3z0rjreb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:n64-solid" /></template>
