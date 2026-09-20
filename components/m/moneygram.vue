<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iosfs0bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iosfs0bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:moneygram" /></template>
