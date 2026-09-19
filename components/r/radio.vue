<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d47xi2b9o.css';
import '../../css/p/pp4ihlbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><circle class="pp4ihlbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:radio" /></template>
