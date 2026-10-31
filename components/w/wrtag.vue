<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9qjclhbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9qjclhbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wrtag" /></template>
