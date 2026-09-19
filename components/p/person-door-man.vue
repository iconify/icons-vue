<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd8zlbb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="qd8zlbb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:person-door-man" /></template>
