<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5m50g79g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5m50g79g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:phone-arrow-up-right" /></template>
