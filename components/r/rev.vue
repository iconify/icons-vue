<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcv1anbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcv1anbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rev" /></template>
