<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfoh1fpvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfoh1fpvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:quote" /></template>
