<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1j9xnt4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1j9xnt4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:printer" /></template>
