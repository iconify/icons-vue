<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ponj89bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ponj89bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-baht" /></template>
