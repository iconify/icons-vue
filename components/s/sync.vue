<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irsxgx7dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irsxgx7dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sync" /></template>
