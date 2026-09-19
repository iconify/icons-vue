<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb52-wqnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb52-wqnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:phone-fill" /></template>
