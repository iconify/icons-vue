<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji5e_cc1a.css';
import '../../css/h/h1ei_9byu.css';
import '../../css/k/kh6xzbb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji5e_cc1a"/><path class="h1ei_9byu"/><path class="kh6xzbb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:pill" /></template>
