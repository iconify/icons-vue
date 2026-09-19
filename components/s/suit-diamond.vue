<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3eon_gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fk3eon_gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:suit-diamond" /></template>
