<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aisklebme.css';
import '../../css/z/z6pi86s9p.css';
import '../../css/p/p_7ey5koq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="aisklebme"/><path class="z6pi86s9p"/><path class="p_7ey5koq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:radio-outline" /></template>
