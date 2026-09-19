<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okph2cb0o.css';
import '../../css/r/r-cemmhlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="okph2cb0o"/><path class="r-cemmhlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torsos" /></template>
