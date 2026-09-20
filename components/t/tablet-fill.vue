<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omt-n94-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="omt-n94-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-fill" /></template>
