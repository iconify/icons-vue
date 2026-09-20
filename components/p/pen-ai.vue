<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv4pscbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv4pscbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pen-ai" /></template>
