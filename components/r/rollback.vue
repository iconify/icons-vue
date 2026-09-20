<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgjjaacpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pgjjaacpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:rollback" /></template>
