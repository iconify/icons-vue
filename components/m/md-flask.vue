<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcbtzpi5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pcbtzpi5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-flask" /></template>
