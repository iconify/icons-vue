<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapzs4b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gapzs4b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:thumbs-down-3" /></template>
