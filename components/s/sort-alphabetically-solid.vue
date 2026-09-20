<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pju9uqsjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pju9uqsjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-alphabetically-solid" /></template>
