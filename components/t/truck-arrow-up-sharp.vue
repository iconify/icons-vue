<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4r3qou8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4r3qou8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-arrow-up-sharp" /></template>
