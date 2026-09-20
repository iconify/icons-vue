<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_bphvlue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_bphvlue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:work-off" /></template>
