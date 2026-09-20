<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq5lxvu6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq5lxvu6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:routing2-filled" /></template>
