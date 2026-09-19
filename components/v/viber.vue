<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfavl6b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfavl6b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:viber" /></template>
