<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jset88bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jset88bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-circle-fill" /></template>
