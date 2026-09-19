<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ds8l59c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="v1ds8l59c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shopping-bag" /></template>
