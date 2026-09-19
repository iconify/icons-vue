<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do2484mdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do2484mdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-up-fill" /></template>
