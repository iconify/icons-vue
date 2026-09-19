<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3mptb1ql.css';
import '../../css/h/hlumq0b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3mptb1ql"/><path class="hlumq0b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:videogame" /></template>
