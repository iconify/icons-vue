<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc0-s1bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":993};
const content = `<path class="hc0-s1bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moneybag" /></template>
