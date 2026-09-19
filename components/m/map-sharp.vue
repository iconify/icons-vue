<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kretn3bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kretn3bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:map-sharp" /></template>
