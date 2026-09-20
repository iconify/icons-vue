<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z917-eb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":163.38};
const content = `<path class="z917-eb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nickelodeon" /></template>
