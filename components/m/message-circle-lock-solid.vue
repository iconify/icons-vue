<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjzzi15jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjzzi15jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-lock-solid" /></template>
