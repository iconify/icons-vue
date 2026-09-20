<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy5by7b9g.css';
import '../../css/g/gld9kyb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jy5by7b9g"/><path class="gld9kyb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:medical-library" /></template>
