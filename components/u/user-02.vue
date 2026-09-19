<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj9sbab8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj9sbab8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-02" /></template>
