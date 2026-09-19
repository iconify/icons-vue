<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf2dofk5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf2dofk5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stomach-outline-24px" /></template>
