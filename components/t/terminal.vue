<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/matslfbya.css';
import '../../css/b/b1ecs5fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="matslfbya"/><path class="b1ecs5fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:terminal" /></template>
