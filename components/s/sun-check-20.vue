<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8nww4mnw.css';
import '../../css/m/mg--uz6gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8nww4mnw"/><path class="mg--uz6gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-check-20" /></template>
