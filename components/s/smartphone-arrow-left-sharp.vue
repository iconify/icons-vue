<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9nhneb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9nhneb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-left-sharp" /></template>
