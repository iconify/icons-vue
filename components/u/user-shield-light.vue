<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbpi54-3i.css';
import '../../css/h/h4vuonvwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbpi54-3i"/><path class="h4vuonvwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-shield-light" /></template>
