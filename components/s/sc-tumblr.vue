<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hia19evqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="hia19evqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-tumblr" /></template>
