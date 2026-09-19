<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c561ylaaj.css';
import '../../css/g/gl5rl746c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c561ylaaj"/><path class="gl5rl746c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:zoom-in" /></template>
