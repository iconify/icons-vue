<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq6g3fbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq6g3fbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-down-left-fill" /></template>
