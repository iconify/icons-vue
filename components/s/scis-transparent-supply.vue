<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b00cr1lqw.css';
import '../../css/k/kbewb6b5s.css';
import '../../css/e/ee744kfgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b00cr1lqw"/><path class="kbewb6b5s"/><path class="ee744kfgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scis-transparent-supply" /></template>
