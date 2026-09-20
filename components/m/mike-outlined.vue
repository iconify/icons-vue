<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apxrc4blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apxrc4blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:mike-outlined" /></template>
