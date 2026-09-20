<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzb3omb7i.css';
import '../../css/x/x9dxbgztj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":60,"height":60};
const content = `<path class="tzb3omb7i"/><path class="x9dxbgztj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unjs" /></template>
