<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqumaeb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qqumaeb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nestjs" /></template>
