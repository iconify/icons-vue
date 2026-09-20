<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2999kb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2999kb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:setting-line" /></template>
