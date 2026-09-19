<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9rnf9u2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":450,"height":512};
const content = `<path class="m9rnf9u2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:webpack-old" /></template>
