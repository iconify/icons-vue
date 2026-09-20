<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbhb5c4wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhb5c4wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:u" /></template>
