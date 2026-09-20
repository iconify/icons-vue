<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8op7gewd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8op7gewd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-check-fill" /></template>
