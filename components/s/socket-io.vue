<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp0bzp2ut.css';
import '../../css/e/epusddcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b tp0bzp2ut"/><path class="b epusddcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:socket-io" /></template>
