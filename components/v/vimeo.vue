<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxys4rbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="cxys4rbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:vimeo" /></template>
