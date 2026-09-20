<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5nf1or0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a5nf1or0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:touch" /></template>
