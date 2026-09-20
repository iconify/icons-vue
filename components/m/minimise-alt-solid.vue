<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km668f46e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="km668f46e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minimise-alt-solid" /></template>
