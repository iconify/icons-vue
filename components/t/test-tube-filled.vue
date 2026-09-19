<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__nbyi8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x__nbyi8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:test-tube-filled" /></template>
