<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj3hfzwqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj3hfzwqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:star-sharp-disabled" /></template>
