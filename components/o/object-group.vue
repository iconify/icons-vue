<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2q5z-wrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2q5z-wrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:object-group" /></template>
