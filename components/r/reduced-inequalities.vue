<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwhv-n8ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pwhv-n8ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:reduced-inequalities" /></template>
