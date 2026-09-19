<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac5n8q2pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac5n8q2pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-06" /></template>
