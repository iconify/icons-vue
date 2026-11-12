<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvabx4bul.css';
import '../../css/o/o217wsq9k.css';
import '../../css/g/gra5yw4ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hvabx4bul"/><path class="o217wsq9k"/><path class="gra5yw4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortarr-dark" /></template>
