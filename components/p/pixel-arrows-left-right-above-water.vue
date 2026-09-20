<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku3j7y3ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ku3j7y3ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrows-left-right-above-water" /></template>
