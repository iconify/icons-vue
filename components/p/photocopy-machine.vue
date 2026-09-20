<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spc03-04k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spc03-04k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:photocopy-machine" /></template>
