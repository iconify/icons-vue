<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce3fwetfj.css';
import '../../css/p/pw5qjybai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ce3fwetfj"/><path class="pw5qjybai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-down-20" /></template>
