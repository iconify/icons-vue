<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6julkbke.css';
import '../../css/t/t5m9mnbka.css';
import '../../css/x/x67cv140v.css';
import '../../css/x/xwei6nojw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t6julkbke"/><path class="t5m9mnbka"/><path class="x67cv140v"/><path class="xwei6nojw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rooftop-wind-20" /></template>
