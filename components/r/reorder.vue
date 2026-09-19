<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6z-3iz4b.css';
import '../../css/w/wpuyqmbtu.css';
import '../../css/l/ln93sbcwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":7,"height":16};
const content = `<circle class="m6z-3iz4b"/><circle class="wpuyqmbtu"/><circle class="ln93sbcwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:reorder" /></template>
