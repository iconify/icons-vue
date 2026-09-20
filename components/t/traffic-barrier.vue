<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjm6qcc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjm6qcc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:traffic-barrier" /></template>
