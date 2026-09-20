<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm3y845ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jm3y845ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-tip-fill" /></template>
