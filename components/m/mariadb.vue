<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d08ecwr6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d08ecwr6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mariadb" /></template>
