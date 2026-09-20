<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjcrkmb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjcrkmb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:message" /></template>
