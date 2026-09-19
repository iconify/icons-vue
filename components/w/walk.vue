<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3qvylb2e.css';
import '../../css/e/e1u7ewaaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="s3qvylb2e"/><path class="e1u7ewaaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:walk" /></template>
