<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbzjrpbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbzjrpbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:x-mark" /></template>
