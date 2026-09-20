<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8l_-fb_k.css';
import '../../css/j/js4-qccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j8l_-fb_k"/><path class="js4-qccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tugtainer" /></template>
