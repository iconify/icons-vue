<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpm-t2bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpm-t2bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-equal-fill" /></template>
