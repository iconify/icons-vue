<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67ggebyw.css';
import '../../css/g/geuo8cbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="g67ggebyw"/><path class="geuo8cbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shoe-11" /></template>
