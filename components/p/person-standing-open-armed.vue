<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r34x9s4nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r34x9s4nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-open-armed" /></template>
