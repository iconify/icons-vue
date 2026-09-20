<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsm-84idg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rsm-84idg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-lying-on-front-in-sun-on-surface" /></template>
