<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my4lljgxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="my4lljgxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-flaming-chalice" /></template>
