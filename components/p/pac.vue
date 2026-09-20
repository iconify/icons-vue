<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_9tr3bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_9tr3bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pac" /></template>
