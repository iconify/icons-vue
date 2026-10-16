<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ily569bri.css';
import '../../css/w/wegqv6blc.css';
import '../../css/z/zsocjwbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ily569bri"/><path class="wegqv6blc"/><path class="zsocjwbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-check-20" /></template>
