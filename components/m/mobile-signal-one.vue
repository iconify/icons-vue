<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmf6dbc6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmf6dbc6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-one" /></template>
