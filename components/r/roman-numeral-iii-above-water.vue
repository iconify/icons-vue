<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr4z8rb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gr4z8rb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-iii-above-water" /></template>
