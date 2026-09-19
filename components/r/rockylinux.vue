<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzo-wiasf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qzo-wiasf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rockylinux" /></template>
