<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug4jnhcxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ug4jnhcxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-circle-outline" /></template>
