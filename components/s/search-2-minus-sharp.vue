<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6h7q7wkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6h7q7wkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-minus-sharp" /></template>
