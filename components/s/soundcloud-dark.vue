<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnrvcab5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnrvcab5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:soundcloud-dark" /></template>
