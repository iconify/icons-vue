<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6s2r5bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6s2r5bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:percent" /></template>
