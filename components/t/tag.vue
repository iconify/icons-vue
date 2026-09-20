<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0jid3ilc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u0jid3ilc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tag" /></template>
