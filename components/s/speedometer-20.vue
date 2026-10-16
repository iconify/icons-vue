<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahflbbcgy.css';
import '../../css/t/twd90018l.css';
import '../../css/u/ut-54jgvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ahflbbcgy"/><path class="twd90018l"/><path class="ut-54jgvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speedometer-20" /></template>
