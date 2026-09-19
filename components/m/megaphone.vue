<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkn1q5bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":32};
const content = `<path class="kkn1q5bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:megaphone" /></template>
