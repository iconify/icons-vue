<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3d6jyb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y3d6jyb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:printables-dark" /></template>
