<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sql9n1bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sql9n1bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-dot-sharp-fill" /></template>
