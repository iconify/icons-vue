<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w51itcb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w51itcb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:signout" /></template>
