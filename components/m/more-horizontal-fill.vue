<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9q_74q2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9q_74q2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:more-horizontal-fill" /></template>
