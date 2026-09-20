<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbajj74xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jbajj74xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:unlock-solid" /></template>
