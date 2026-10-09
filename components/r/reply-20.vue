<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gypgls1dd.css';
import '../../css/e/ems1_nb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gypgls1dd"/><path class="ems1_nb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reply-20" /></template>
