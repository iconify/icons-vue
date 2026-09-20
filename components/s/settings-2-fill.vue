<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gppv4vhln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gppv4vhln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-2-fill" /></template>
