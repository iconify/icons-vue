<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujh6q_bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujh6q_bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-circle-sharp" /></template>
