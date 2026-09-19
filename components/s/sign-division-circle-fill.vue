<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pew7ey2cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pew7ey2cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-circle-fill" /></template>
