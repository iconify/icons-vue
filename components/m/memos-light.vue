<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz1qd9m1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz1qd9m1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:memos-light" /></template>
