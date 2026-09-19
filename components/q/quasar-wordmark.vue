<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1o-oykdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c1o-oykdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:quasar-wordmark" /></template>
