<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi-wf1bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi-wf1bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:organization-outlined" /></template>
