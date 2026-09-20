<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsdaybuea.css';
import '../../css/t/tx00macjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hsdaybuea"/><path class="tx00macjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:spell-check-16" /></template>
