<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un-wte4cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="un-wte4cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nuget" /></template>
