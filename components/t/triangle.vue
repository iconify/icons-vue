<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb29_fb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb29_fb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:triangle" /></template>
