<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1j7ehxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jg1j7ehxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:smartphone-notch" /></template>
