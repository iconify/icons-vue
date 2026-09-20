<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5h6isb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g5h6isb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nhibernate" /></template>
