<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asx1s34lr.css';
import '../../css/l/l7gyyf0so.css';
import '../../css/x/xuvtw8qyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="asx1s34lr"/><path class="l7gyyf0so"/><path class="xuvtw8qyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pelton-wheel-20" /></template>
