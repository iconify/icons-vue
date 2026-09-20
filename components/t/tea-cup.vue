<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz1pcacve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz1pcacve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tea-cup" /></template>
