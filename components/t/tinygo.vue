<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltbdwbc7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ltbdwbc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:tinygo" /></template>
