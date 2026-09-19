<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya8morbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya8morbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:send" /></template>
