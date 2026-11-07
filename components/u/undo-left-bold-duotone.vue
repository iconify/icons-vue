<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0stl6voo.css';
import '../../css/h/hcm7vlw8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0stl6voo"/><path class="hcm7vlw8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-left-bold-duotone" /></template>
