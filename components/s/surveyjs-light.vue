<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na6dr8byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="na6dr8byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surveyjs-light" /></template>
