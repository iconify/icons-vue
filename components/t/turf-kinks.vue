<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/togxi8l0i.css';
import '../../css/c/c4i61rb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="togxi8l0i"/><circle class="c4i61rb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-kinks" /></template>
