<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vom0lbury.css';
import '../../css/z/zueniel6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vom0lbury"/><path clip-rule="evenodd" class="zueniel6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-right-close-outline" /></template>
