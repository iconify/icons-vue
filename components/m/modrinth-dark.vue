<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5v0c1bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5v0c1bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:modrinth-dark" /></template>
