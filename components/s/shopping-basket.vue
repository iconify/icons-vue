<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo_3ecfhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jo_3ecfhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:shopping-basket" /></template>
