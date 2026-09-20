<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy6di_b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6di_b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wifi" /></template>
