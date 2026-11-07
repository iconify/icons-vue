<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqeyqsb0i.css';
import '../../css/d/dek9bkq9j.css';
import '../../css/s/svjtfbbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqeyqsb0i"/><path class="dek9bkq9j"/><path clip-rule="evenodd" class="svjtfbbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-bold" /></template>
