<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im5jvnb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im5jvnb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-plus-sharp-fill" /></template>
