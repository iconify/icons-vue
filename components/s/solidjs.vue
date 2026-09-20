<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ynjz1cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ynjz1cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:solidjs" /></template>
