<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_cq0-cvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_cq0-cvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-pets-allowed" /></template>
