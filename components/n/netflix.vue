<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmg3tqb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmg3tqb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:netflix" /></template>
