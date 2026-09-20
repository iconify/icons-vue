<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah8g6_bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8g6_bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:shopping-bag-fill" /></template>
