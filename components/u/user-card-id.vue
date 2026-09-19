<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya9b5bb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9b5bb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:user-card-id" /></template>
