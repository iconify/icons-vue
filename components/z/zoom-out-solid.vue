<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fan6-n1tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fan6-n1tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zoom-out-solid" /></template>
