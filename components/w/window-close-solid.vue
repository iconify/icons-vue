<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3lnfob0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3lnfob0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:window-close-solid" /></template>
