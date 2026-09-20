<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6q8gwb1h.css';
import '../../css/k/k6dzamvnj.css';
import '../../css/u/uc0jhbc1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l6q8gwb1h"/><path class="k6dzamvnj"/><path class="uc0jhbc1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sushi" /></template>
