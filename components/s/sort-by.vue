<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpkdf3o7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="vpkdf3o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:sort-by" /></template>
