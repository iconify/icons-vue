<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0vkn9zgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0vkn9zgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:planet-solid" /></template>
