<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uckaycc9t.css';
import '../../css/t/t170-qrdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uckaycc9t"/><path class="t170-qrdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:settings-20" /></template>
