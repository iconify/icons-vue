<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agxzxbcvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agxzxbcvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-outline" /></template>
