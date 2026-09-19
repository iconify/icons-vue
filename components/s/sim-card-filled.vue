<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-k13z9jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-k13z9jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sim-card-filled" /></template>
