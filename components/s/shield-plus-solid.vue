<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi4z6zb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi4z6zb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-plus-solid" /></template>
