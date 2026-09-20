<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jomceu7fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jomceu7fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skateboard" /></template>
