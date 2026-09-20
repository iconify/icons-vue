<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gojrobtkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gojrobtkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:missed-call" /></template>
