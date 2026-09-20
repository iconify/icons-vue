<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-nqdb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ex-nqdb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:thumb-down-outline" /></template>
