<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtchp6bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtchp6bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:navigate-circle-sharp" /></template>
