<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abv-ihbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abv-ihbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:phone-filled" /></template>
