<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-j1icbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-j1icbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:moon-sharp" /></template>
