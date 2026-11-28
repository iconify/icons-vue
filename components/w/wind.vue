<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvakp6a-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvakp6a-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wind" /></template>
