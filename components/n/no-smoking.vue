<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk5rj2xsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mk5rj2xsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:no-smoking" /></template>
