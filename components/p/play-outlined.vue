<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifwdv1pih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifwdv1pih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:play-outlined" /></template>
