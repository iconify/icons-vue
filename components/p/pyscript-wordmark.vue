<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzs4d4blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zzs4d4blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pyscript-wordmark" /></template>
