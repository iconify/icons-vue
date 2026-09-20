<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5hfmr3-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="e5hfmr3-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:school-11" /></template>
