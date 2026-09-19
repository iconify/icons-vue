<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6riy61-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="s6riy61-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:odnoklassniki-rect" /></template>
