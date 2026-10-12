<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta4ildugp.css';
import '../../css/g/gda8q7btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ta4ildugp"/><path class="gda8q7btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:notebook-48-bold" /></template>
