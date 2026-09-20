<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m119fqbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m119fqbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-pen-outline" /></template>
