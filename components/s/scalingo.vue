<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9_6bmb7k.css';
import '../../css/e/ebvmgs0jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c9_6bmb7k"/><path class="ebvmgs0jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scalingo" /></template>
