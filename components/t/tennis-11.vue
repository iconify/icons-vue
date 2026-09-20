<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-27md8lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="g-27md8lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:tennis-11" /></template>
