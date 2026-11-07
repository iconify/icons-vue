<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1uxr3i-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1uxr3i-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-angular-outline" /></template>
