<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvd0dvxai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvd0dvxai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget5" /></template>
