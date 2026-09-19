<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq300m9xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq300m9xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:night-light-filled" /></template>
