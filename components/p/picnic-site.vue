<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ush4msblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ush4msblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:picnic-site" /></template>
