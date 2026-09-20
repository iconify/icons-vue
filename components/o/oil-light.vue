<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy0-_fo1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy0-_fo1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:oil-light" /></template>
