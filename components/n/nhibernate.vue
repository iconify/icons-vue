<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aecai_kku.css';
import '../../css/g/g-d1ckdau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aecai_kku"/><path class="g-d1ckdau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nhibernate" /></template>
