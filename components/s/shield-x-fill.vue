<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm9szy78b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm9szy78b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-x-fill" /></template>
