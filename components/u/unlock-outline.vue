<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn8fv0bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tn8fv0bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:unlock-outline" /></template>
