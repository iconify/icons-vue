<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n82y8wbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n82y8wbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:testrail" /></template>
