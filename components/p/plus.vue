<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4e6zl6iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y4e6zl6iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:plus" /></template>
