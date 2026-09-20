<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2eidcoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_2eidcoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:syringe-outline" /></template>
