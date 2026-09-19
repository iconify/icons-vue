<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8phsb1v.css';
import '../../css/r/rzz4edc1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ci8phsb1v"/><path class="rzz4edc1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:megaphone-stroke-16" /></template>
