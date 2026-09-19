<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-8yqkjzv.css';
import '../../css/u/u3odm3brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-8yqkjzv"/><path class="u3odm3brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:wallet" /></template>
