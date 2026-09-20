<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqkcty9kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eqkcty9kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:marker-15" /></template>
