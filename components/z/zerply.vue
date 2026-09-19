<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz_2ei_9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":336,"height":488};
const content = `<path class="rz_2ei_9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:zerply" /></template>
