<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl-abrbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bl-abrbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-binary" /></template>
