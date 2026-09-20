<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owkn8rban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owkn8rban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-merge" /></template>
