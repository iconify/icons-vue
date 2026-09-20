<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjyp3pbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pjyp3pbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:next-circle-outline" /></template>
