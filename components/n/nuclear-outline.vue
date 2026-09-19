<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6xt5c87v.css';
import '../../css/a/a-9mugb1d.css';
import '../../css/u/up6r22q7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="j6xt5c87v"/><circle class="a-9mugb1d"/><path class="up6r22q7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:nuclear-outline" /></template>
