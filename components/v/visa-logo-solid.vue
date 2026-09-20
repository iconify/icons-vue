<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2op8db_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2op8db_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:visa-logo-solid" /></template>
