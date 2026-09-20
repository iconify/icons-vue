<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jypyrtbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jypyrtbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sort-alfa-light" /></template>
