<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spd40nbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="spd40nbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shield-fill-20" /></template>
