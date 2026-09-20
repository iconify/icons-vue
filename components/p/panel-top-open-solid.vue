<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhkdmcvso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhkdmcvso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-top-open-solid" /></template>
