<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr-mm0bik.css';
import '../../css/f/f_pk9vbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kr-mm0bik"/><path class="f_pk9vbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermistor-20" /></template>
