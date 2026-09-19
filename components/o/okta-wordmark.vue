<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7e5t-z9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u7e5t-z9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:okta-wordmark" /></template>
