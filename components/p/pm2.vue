<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2n6zrbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v2n6zrbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pm2" /></template>
