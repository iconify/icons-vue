<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1dwfbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1dwfbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-minus-sharp" /></template>
