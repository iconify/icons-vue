<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0fjq6bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g0fjq6bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:opensuse" /></template>
