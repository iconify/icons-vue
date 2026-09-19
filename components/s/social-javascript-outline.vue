<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9kdxsbyj.css';
import '../../css/s/skl1w_bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9kdxsbyj"/><path class="skl1w_bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-javascript-outline" /></template>
