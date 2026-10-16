<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqpralk8i.css';
import '../../css/r/rfhud25gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqpralk8i"/><path class="rfhud25gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tower-section-20" /></template>
