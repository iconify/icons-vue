<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z73ncbczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":610,"height":850};
const content = `<path class="z73ncbczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:user" /></template>
