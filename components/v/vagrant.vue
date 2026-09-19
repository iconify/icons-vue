<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4ihg-sz.css';
import '../../css/x/x3brn5b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fu4ihg-sz"/><path class="x3brn5b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vagrant" /></template>
