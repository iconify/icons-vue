<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw6l45h2h.css';
import '../../css/c/c89ohuy8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uw6l45h2h"/><path class="c89ohuy8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:zip-wire" /></template>
