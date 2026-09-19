<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1b4lydev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b4lydev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tv" /></template>
