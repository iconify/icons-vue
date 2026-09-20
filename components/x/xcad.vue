<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-vo9kzaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vo9kzaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xcad" /></template>
