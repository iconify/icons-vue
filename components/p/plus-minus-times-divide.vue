<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt9zmbbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt9zmbbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plus-minus-times-divide" /></template>
