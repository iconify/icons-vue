<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2ehimbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2ehimbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:rating-star-three" /></template>
