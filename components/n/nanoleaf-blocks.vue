<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbzkpjb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbzkpjb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-blocks" /></template>
