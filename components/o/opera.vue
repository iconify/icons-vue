<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5eussbda.css';
import '../../css/e/e6n3rcb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5eussbda"/><path class="e6n3rcb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:opera" /></template>
