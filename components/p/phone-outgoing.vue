<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa96e2l9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa96e2l9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-outgoing" /></template>
