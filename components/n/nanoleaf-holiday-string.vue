<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3hc92b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3hc92b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-holiday-string" /></template>
