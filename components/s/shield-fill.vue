<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg198ngpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cg198ngpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-fill" /></template>
