<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukjdqe4vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukjdqe4vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:phone-actions-off" /></template>
