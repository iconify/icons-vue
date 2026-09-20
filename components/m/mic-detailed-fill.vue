<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjv0t2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjv0t2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mic-detailed-fill" /></template>
