<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkser5_na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kkser5_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-311" /></template>
