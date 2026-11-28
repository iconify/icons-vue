<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prjme_zsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prjme_zsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pill-solid" /></template>
