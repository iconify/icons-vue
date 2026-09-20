<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi8be4b8f.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rb6z_dbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGe8XTUbxL" class="xi8be4b8f"/></defs><mask id="SVGpZtlpbaw" class="cuyn6tgcc"><use href="#SVGe8XTUbxL"/></mask><g class="cuyn6tgcc"><use href="#SVGe8XTUbxL"/><path mask="url(#SVGpZtlpbaw)" class="rb6z_dbtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:panel-bottom-minimized" /></template>
