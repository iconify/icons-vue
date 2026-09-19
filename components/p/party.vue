<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmd0fo11n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmd0fo11n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:party" /></template>
