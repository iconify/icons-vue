<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0g9nac6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g9nac6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:turtle-solid" /></template>
