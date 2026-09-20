<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx85mubpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bx85mubpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:menu-solid" /></template>
