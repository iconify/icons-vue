<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eypp7rb0r.css';
import '../../css/a/a224fdcsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="eypp7rb0r"/><path clip-rule="evenodd" class="a224fdcsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:weight-machine-1" /></template>
