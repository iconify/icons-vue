<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsf1w7y6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsf1w7y6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-right-sharp" /></template>
