<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eme4g79qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eme4g79qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-lower" /></template>
