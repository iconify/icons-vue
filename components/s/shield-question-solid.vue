<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od81eqt0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od81eqt0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-question-solid" /></template>
