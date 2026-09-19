<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz7n-pn_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uz7n-pn_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:xamarin-wordmark" /></template>
