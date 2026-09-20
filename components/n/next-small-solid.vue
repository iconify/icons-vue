<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx4jh9g-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fx4jh9g-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:next-small-solid" /></template>
