<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_f-8ebio.css';
import '../../css/d/dmqvb9ndz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_f-8ebio"/><path class="dmqvb9ndz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:terra-classic" /></template>
